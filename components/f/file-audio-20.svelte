<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szahujb-p.css';
import '../../css/b/btgf0khhi.css';
import '../../css/a/ar8noqkkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="btgf0khhi"/><path class="ar8noqkkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-audio-20" {...props}></Icon>
