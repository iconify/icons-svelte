<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yze8n3h-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yze8n3h-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:alarm-clock-small-filled" {...props}></Icon>
