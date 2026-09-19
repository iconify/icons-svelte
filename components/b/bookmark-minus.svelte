<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjvd_wblo.css';
import '../../css/b/bs7jjo5xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjvd_wblo"/><path class="bs7jjo5xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:bookmark-minus" {...props}></Icon>
