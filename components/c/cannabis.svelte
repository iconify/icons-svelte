<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_i5kvbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_i5kvbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cannabis" {...props}></Icon>
