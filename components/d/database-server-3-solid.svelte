<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxf1p3ugb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gxf1p3ugb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:database-server-3-solid" {...props}></Icon>
