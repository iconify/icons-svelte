<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpmof_b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jpmof_b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-down-right" {...props}></Icon>
