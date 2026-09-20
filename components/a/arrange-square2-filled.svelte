<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de9w25bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de9w25bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrange-square2-filled" {...props}></Icon>
