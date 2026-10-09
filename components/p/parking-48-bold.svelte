<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkarr2bij.css';
import '../../css/c/ctcoo0l_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kkarr2bij"/><path class="ctcoo0l_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parking-48-bold" {...props}></Icon>
