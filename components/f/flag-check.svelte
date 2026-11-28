<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f61n8eakj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f61n8eakj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flag-check" {...props}></Icon>
