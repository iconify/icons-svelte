<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k40yvq1wf.css';
import '../../css/e/e1pitrb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k40yvq1wf"/><path class="e1pitrb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:italic-20-bold" {...props}></Icon>
