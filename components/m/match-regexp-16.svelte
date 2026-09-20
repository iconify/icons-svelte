<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf-bn_bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cf-bn_bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:match-regexp-16" {...props}></Icon>
