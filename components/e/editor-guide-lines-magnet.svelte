<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pat_cd9rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pat_cd9rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:editor-guide-lines-magnet" {...props}></Icon>
