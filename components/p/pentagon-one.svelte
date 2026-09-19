<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgh0_tp3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hgh0_tp3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:pentagon-one" {...props}></Icon>
