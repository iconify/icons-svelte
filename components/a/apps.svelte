<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5rdg-bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o5rdg-bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:apps" {...props}></Icon>
