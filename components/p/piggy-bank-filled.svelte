<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddpxg66go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddpxg66go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:piggy-bank-filled" {...props}></Icon>
