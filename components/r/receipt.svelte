<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfmcxfo2r.css';
import '../../css/r/rt4k2lbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfmcxfo2r"/><path class="rt4k2lbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:receipt" {...props}></Icon>
