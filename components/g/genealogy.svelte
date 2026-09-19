<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvir7eh3z.css';
import '../../css/c/c4bzylu5l.css';
import '../../css/m/m3lczlbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uvir7eh3z"/><path class="c4bzylu5l"/><path class="m3lczlbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:genealogy" {...props}></Icon>
