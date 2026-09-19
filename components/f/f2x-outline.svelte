<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7srihbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m7srihbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:f2x-outline" {...props}></Icon>
