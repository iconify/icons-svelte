<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpwe93btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpwe93btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-m-diamond-solid" {...props}></Icon>
