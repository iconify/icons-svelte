<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc12bymlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc12bymlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pause" {...props}></Icon>
