<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugd2fac-m.css';
import '../../css/x/x5g82_bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ugd2fac-m"/><path class="x5g82_bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:owl-48-bold" {...props}></Icon>
