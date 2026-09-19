<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek4_hnsal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ek4_hnsal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dropbox-square" {...props}></Icon>
