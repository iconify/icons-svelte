<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owl0rtbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owl0rtbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-square" {...props}></Icon>
