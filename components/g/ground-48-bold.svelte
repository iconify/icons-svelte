<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpggqk6re.css';
import '../../css/e/e75wleedx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jpggqk6re"/><path class="e75wleedx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-48-bold" {...props}></Icon>
