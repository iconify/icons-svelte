<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7fu7w2an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7fu7w2an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-square-solid" {...props}></Icon>
