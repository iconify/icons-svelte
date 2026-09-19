<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_6hphyay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_6hphyay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:comic-bubble-filled" {...props}></Icon>
