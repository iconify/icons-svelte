<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd0hhnbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd0hhnbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bridge-solid" {...props}></Icon>
