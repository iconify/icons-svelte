<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlxtf-b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qlxtf-b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:3" {...props}></Icon>
