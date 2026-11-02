<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo1tmdbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo1tmdbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cable-fill" {...props}></Icon>
