<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx9_onrig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gx9_onrig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:like" {...props}></Icon>
