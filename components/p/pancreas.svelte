<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld3frub9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ld3frub9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pancreas" {...props}></Icon>
