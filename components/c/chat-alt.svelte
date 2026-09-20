<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e__idhb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="e__idhb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:chat-alt" {...props}></Icon>
