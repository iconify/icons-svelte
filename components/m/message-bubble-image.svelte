<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5v5asbue.css';
import '../../css/z/zbxahybdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5v5asbue"/><path class="zbxahybdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-image" {...props}></Icon>
