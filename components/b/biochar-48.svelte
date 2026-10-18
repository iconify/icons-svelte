<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa1bric-y.css';
import '../../css/s/s_f2_dbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sa1bric-y"/><path class="s_f2_dbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:biochar-48" {...props}></Icon>
