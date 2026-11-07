<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/conyuxbxt.css';
import '../../css/v/vlg3w9b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="conyuxbxt"/><path class="vlg3w9b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-bold" {...props}></Icon>
