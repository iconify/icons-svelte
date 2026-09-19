<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pppqz8-bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pppqz8-bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-filled" {...props}></Icon>
