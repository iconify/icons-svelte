<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utf77lbef.css';
import '../../css/l/lrtwh708v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="lrtwh708v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-step-48" {...props}></Icon>
