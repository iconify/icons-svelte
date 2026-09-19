<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmyun8gui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jmyun8gui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:excel-logo-outline" {...props}></Icon>
