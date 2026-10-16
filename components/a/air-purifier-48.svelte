<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyz2fo8fs.css';
import '../../css/e/ecbqf8bde.css';
import '../../css/q/qs6411b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kyz2fo8fs"/><path class="ecbqf8bde"/><path class="qs6411b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-purifier-48" {...props}></Icon>
