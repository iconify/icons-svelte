<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrqlv4q8g.css';
import '../../css/g/gc181eckg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrqlv4q8g"/><path class="gc181eckg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendars-filled" {...props}></Icon>
