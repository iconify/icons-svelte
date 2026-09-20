<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asaqj9qwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asaqj9qwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:podium" {...props}></Icon>
