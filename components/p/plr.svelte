<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg4gvs8ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zg4gvs8ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:plr" {...props}></Icon>
