<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp-2r9b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vp-2r9b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:airport-security-remix" {...props}></Icon>
