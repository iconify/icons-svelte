<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb70uhhrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<path class="tb70uhhrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bottom-bar-one" {...props}></Icon>
