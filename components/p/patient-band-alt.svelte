<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buyk58chx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="buyk58chx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:patient-band-alt" {...props}></Icon>
