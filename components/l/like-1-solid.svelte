<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upt28hb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="upt28hb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:like-1-solid" {...props}></Icon>
