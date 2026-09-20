<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_n-l9b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_n-l9b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-square" {...props}></Icon>
