<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7zyorbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e7zyorbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:flashlight-solid" {...props}></Icon>
