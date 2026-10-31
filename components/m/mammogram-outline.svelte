<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnnpbobrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mnnpbobrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mammogram-outline" {...props}></Icon>
