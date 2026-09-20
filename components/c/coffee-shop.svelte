<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgzl3pbub.css';
import '../../css/y/yixh8cciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dgzl3pbub"/><path class="yixh8cciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:coffee-shop" {...props}></Icon>
