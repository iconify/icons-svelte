<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i91rgtb8j.css';
import '../../css/w/wohdjobkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i91rgtb8j"/><path class="wohdjobkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:edit-fill" {...props}></Icon>
