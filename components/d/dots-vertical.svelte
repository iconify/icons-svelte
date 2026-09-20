<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn5adcdwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn5adcdwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical" {...props}></Icon>
