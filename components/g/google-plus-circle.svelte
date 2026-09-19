<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftf_zu7ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ftf_zu7ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:google-plus-circle" {...props}></Icon>
