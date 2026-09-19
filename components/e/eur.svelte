<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6qp5mb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o6qp5mb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:eur" {...props}></Icon>
