<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i33_62bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="i33_62bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-text-solid" {...props}></Icon>
