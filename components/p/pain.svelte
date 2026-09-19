<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myfolab4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="myfolab4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pain" {...props}></Icon>
