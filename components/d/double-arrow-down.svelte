<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inw8n8b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inw8n8b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:double-arrow-down" {...props}></Icon>
