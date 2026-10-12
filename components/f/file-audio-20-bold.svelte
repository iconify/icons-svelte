<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccsyvk3j.css';
import '../../css/w/wao0dvbdb.css';
import '../../css/g/g-h11i9wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="wao0dvbdb"/><path class="g-h11i9wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-audio-20-bold" {...props}></Icon>
