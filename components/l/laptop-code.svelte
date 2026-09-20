<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqh5qzb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zqh5qzb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:laptop-code" {...props}></Icon>
