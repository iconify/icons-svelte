<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reoap2bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="reoap2bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:one-one" {...props}></Icon>
