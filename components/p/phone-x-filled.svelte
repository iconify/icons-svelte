<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddpxy9bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddpxy9bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-x-filled" {...props}></Icon>
