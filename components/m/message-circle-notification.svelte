<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or6rs0b6f.css';
import '../../css/p/pgigtuv7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="pgigtuv7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-notification" {...props}></Icon>
