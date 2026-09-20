<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uejwkwmst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="uejwkwmst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-right" {...props}></Icon>
