<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j501ubcbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j501ubcbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-a-solid" {...props}></Icon>
