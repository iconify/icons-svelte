<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd6_tobvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wd6_tobvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:block" {...props}></Icon>
