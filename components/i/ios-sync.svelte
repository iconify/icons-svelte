<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naq0tfbis.css';
import '../../css/p/pkado8zjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="naq0tfbis"/><path class="pkado8zjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-sync" {...props}></Icon>
