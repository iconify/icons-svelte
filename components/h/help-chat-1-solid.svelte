<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9l2s-gon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y9l2s-gon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:help-chat-1-solid" {...props}></Icon>
