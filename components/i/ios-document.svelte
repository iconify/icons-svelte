<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blhdngppl.css';
import '../../css/c/cnc6799tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blhdngppl"/><path class="cnc6799tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-document" {...props}></Icon>
