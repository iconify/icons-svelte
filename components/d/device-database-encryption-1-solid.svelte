<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oal5ot4fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oal5ot4fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:device-database-encryption-1-solid" {...props}></Icon>
