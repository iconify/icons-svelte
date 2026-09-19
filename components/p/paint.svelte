<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cozlh9whk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cozlh9whk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:paint" {...props}></Icon>
