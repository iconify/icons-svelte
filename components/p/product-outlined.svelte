<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irwz_dnyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="irwz_dnyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:product-outlined" {...props}></Icon>
