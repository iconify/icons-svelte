<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilmos39e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilmos39e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:piggy-bank-solid" {...props}></Icon>
