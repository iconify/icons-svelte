<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gylj85but.css';
import '../../css/d/d1rsb2bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gylj85but"/><path class="d1rsb2bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-dual-48-bold" {...props}></Icon>
