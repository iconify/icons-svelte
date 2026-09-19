<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0mi_2b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t0mi_2b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:62x-outline" {...props}></Icon>
