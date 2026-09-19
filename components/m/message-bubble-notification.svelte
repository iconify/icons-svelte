<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or6rs0b6f.css';
import '../../css/s/st00gj83u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="st00gj83u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-notification" {...props}></Icon>
