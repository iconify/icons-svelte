<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klt4mrzdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="klt4mrzdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gym" {...props}></Icon>
