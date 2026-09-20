<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbqnbpbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbqnbpbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-graduation-outline" {...props}></Icon>
