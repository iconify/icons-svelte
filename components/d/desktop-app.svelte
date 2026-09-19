<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge6-751ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ge6-751ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:desktop-app" {...props}></Icon>
