<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc316fo5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc316fo5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-right-bottom" {...props}></Icon>
