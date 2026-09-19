<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm6lhw1sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dm6lhw1sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:e" {...props}></Icon>
