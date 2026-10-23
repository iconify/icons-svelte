<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up1io4b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="up1io4b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactating-outline" {...props}></Icon>
