<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvggpac7z.css';
import '../../css/l/lu4zihdbk.css';
import '../../css/m/mg7ihkb7k.css';
import '../../css/d/d-rurg29d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="lu4zihdbk"/><path class="mg7ihkb7k"/><path class="d-rurg29d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-snowflake-48" {...props}></Icon>
