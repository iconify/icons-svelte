<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0esvozoi.css';
import '../../css/y/ykhcx6d8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j0esvozoi"/><path class="ykhcx6d8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:application-web" {...props}></Icon>
