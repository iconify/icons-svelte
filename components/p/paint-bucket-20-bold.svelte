<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioqh6lbvj.css';
import '../../css/n/nhtywxbko.css';
import '../../css/q/qz4s_4byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ioqh6lbvj"/><path class="nhtywxbko"/><path class="qz4s_4byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paint-bucket-20-bold" {...props}></Icon>
