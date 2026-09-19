<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykjovtd5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ykjovtd5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-two" {...props}></Icon>
