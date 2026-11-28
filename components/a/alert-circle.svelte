<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg5aatbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5aatbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:alert-circle" {...props}></Icon>
