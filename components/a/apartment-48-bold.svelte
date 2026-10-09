<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpmgkheit.css';
import '../../css/r/rw5av3bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hpmgkheit"/><path class="rw5av3bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apartment-48-bold" {...props}></Icon>
