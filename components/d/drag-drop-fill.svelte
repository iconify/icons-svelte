<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia27gz4hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia27gz4hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drag-drop-fill" {...props}></Icon>
