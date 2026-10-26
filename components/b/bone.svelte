<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbsa_4bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vbsa_4bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bone" {...props}></Icon>
