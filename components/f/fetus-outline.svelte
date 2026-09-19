<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irfh52bua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="irfh52bua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:fetus-outline" {...props}></Icon>
