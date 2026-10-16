<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr4vd1rvr.css';
import '../../css/k/k16_ngbvw.css';
import '../../css/v/vlj26f7td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wr4vd1rvr"/><path class="k16_ngbvw"/><path class="vlj26f7td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-input-48" {...props}></Icon>
