<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp2-90bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vp2-90bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:alien-solid" {...props}></Icon>
