<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynhhlqb6o.css';
import '../../css/c/cfetz3bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="cfetz3bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:copyleft" {...props}></Icon>
