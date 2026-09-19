<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm7ljybas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nm7ljybas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:fingerprint" {...props}></Icon>
