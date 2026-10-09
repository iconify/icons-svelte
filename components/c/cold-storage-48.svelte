<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lji_pzt1f.css';
import '../../css/y/ymlv-kbac.css';
import '../../css/m/mg7ihkb7k.css';
import '../../css/d/d-rurg29d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lji_pzt1f"/><path class="ymlv-kbac"/><path class="mg7ihkb7k"/><path class="d-rurg29d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cold-storage-48" {...props}></Icon>
