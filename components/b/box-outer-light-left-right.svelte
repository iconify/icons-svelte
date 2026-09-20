<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnhwlnb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qnhwlnb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-left-right" {...props}></Icon>
