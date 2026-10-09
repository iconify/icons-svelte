<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okzvs_blx.css';
import '../../css/g/gu1a-jb1z.css';
import '../../css/t/tvwqtv2ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="okzvs_blx"/><path class="gu1a-jb1z"/><path class="tvwqtv2ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-keyhole-20" {...props}></Icon>
