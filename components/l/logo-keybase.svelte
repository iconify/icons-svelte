<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydf994boj.css';
import '../../css/e/ev5zxibtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ydf994boj"/><path class="ev5zxibtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-keybase" {...props}></Icon>
