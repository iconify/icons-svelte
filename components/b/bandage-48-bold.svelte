<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joh4xhb-o.css';
import '../../css/m/md8r-wrpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="joh4xhb-o"/><path class="md8r-wrpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bandage-48-bold" {...props}></Icon>
