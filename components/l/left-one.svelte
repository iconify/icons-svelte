<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq68aybud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dq68aybud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:left-one" {...props}></Icon>
