<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynj33xbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynj33xbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-telegram-solid" {...props}></Icon>
