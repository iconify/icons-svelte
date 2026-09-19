<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or1av_2jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or1av_2jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:home-x" {...props}></Icon>
