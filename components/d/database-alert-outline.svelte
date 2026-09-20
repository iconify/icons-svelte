<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wumm18bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wumm18bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-alert-outline" {...props}></Icon>
