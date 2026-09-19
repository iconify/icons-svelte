<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7dwa2e_z.css';
import '../../css/w/wd-20gb_a.css';
import '../../css/g/gzv9kc5wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t7dwa2e_z"/><path class="wd-20gb_a"/><path class="gzv9kc5wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:pie-chart" {...props}></Icon>
