<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9ql8lx2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9ql8lx2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-circle-outline" {...props}></Icon>
