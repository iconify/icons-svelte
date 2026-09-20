<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txm3c8rvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txm3c8rvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:home-plus" {...props}></Icon>
