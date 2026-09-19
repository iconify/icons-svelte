<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3szy1brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q3szy1brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bridge-one" {...props}></Icon>
