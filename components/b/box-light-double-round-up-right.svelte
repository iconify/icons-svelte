<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8q0zdbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="c8q0zdbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-double-round-up-right" {...props}></Icon>
