<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj71y7bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj71y7bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-equal-solid" {...props}></Icon>
