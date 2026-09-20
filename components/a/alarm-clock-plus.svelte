<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo-uomb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo-uomb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alarm-clock-plus" {...props}></Icon>
