<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuggqv5-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuggqv5-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-x-circle-solid" {...props}></Icon>
