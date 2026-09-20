<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dks-8vbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dks-8vbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:incognito-off" {...props}></Icon>
