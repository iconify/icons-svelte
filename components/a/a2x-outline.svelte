<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxjk7zwzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hxjk7zwzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:a2x-outline" {...props}></Icon>
