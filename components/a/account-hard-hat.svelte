<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xno0b68zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xno0b68zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-hard-hat" {...props}></Icon>
