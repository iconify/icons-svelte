<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0yg9djzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0yg9djzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-minus" {...props}></Icon>
