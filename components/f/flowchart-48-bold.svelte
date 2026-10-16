<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iehgmbc0b.css';
import '../../css/x/x2zs-zbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iehgmbc0b"/><path class="x2zs-zbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flowchart-48-bold" {...props}></Icon>
