<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za30h5bbb.css';
import '../../css/n/no53kdbqh.css';
import '../../css/l/lr5jr9ons.css';
import '../../css/x/xopzt8bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="za30h5bbb"/><path class="no53kdbqh"/><path class="lr5jr9ons"/><path class="xopzt8bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:peatland-48" {...props}></Icon>
