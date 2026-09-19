<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsb-q4fqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zsb-q4fqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:list-tree" {...props}></Icon>
