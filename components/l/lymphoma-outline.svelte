<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2pn15bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v2pn15bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lymphoma-outline" {...props}></Icon>
