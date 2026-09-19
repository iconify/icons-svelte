<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb-tf8bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="tb-tf8bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dislike" {...props}></Icon>
