<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4crdmbww.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/y/yr1454spc.css';
import '../../css/f/fdlxrep5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4crdmbww"/><path class="hwjgqrbah"/><path class="yr1454spc"/><path class="fdlxrep5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-plus-48-bold" {...props}></Icon>
