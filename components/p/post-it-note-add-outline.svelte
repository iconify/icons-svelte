<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaiv0cbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaiv0cbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:post-it-note-add-outline" {...props}></Icon>
