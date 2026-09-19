<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-r86ne6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w-r86ne6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:qtum" {...props}></Icon>
