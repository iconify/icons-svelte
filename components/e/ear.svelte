<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggto-wb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ggto-wb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ear" {...props}></Icon>
