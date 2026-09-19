<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxoppz7ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gxoppz7ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lymph-nodes-outline" {...props}></Icon>
