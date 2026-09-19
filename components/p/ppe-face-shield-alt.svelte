<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbgu9-blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vbgu9-blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-face-shield-alt" {...props}></Icon>
