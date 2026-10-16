<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8314acox.css';
import '../../css/s/sy3lcl67n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o8314acox"/><path class="sy3lcl67n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:captions-48-bold" {...props}></Icon>
