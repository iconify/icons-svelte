<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbxahob9m.css';
import '../../css/d/d7h047u_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xbxahob9m"/><path class="d7h047u_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contact-48" {...props}></Icon>
