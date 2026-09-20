<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hicpc4xzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hicpc4xzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-octagon-solid" {...props}></Icon>
