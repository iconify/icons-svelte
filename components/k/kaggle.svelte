<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko686hmhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ko686hmhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:kaggle" {...props}></Icon>
