<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5x9ex2ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5x9ex2ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-only-one-to-zero-or-one" {...props}></Icon>
