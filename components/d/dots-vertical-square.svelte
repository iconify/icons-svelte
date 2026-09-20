<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmoklgqjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmoklgqjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-square" {...props}></Icon>
