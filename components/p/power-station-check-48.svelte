<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-mlap11n.css';
import '../../css/v/vkcjghb5f.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d-mlap11n"/><path class="vkcjghb5f"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-check-48" {...props}></Icon>
