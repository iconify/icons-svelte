<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if7_acbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if7_acbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:milk-bottle-filled" {...props}></Icon>
