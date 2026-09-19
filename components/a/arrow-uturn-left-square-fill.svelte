<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu28e69yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yu28e69yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-left-square-fill" {...props}></Icon>
