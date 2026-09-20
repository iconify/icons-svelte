<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhjp9ab2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zhjp9ab2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:layout-right-sidebar-solid" {...props}></Icon>
