<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct79oziwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct79oziwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-4-filled" {...props}></Icon>
