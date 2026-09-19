<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynhhlqb6o.css';
import '../../css/m/m1wo2_c3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="m1wo2_c3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:registered-trademark" {...props}></Icon>
