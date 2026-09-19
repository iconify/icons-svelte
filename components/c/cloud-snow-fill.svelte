<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzs9y6jfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fzs9y6jfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-snow-fill" {...props}></Icon>
