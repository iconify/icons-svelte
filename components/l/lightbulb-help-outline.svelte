<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np4njztvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np4njztvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-help-outline" {...props}></Icon>
