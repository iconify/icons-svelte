<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj-zwf-qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fj-zwf-qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:add" {...props}></Icon>
