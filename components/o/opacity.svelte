<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voozf6bkw.css';
import '../../css/x/xewwv3l1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="voozf6bkw"/><path class="xewwv3l1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:opacity" {...props}></Icon>
