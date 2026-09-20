<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho3_thbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho3_thbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt-text-arrow-left-outline" {...props}></Icon>
