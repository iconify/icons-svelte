<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_bf7b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vg_bf7b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:game-emoji" {...props}></Icon>
