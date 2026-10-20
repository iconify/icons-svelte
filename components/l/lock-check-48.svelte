<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th_2c0ilx.css';
import '../../css/n/nv4ijsbik.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="th_2c0ilx"/><path class="nv4ijsbik"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-check-48" {...props}></Icon>
