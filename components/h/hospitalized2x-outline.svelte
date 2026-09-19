<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0-vmgb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b0-vmgb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:hospitalized2x-outline" {...props}></Icon>
