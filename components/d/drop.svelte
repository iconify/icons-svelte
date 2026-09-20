<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtd0qyxek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtd0qyxek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:drop" {...props}></Icon>
