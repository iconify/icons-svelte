<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyj46dbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyj46dbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:light-line" {...props}></Icon>
