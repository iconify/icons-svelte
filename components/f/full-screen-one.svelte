<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbywh-bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zbywh-bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:full-screen-one" {...props}></Icon>
