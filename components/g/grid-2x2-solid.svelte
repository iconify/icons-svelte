<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbnwhwoyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbnwhwoyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grid-2x2-solid" {...props}></Icon>
