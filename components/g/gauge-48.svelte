<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmmt3ebdz.css';
import '../../css/f/ftjyp7crf.css';
import '../../css/q/qeutyabff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmmt3ebdz"/><path class="ftjyp7crf"/><path class="qeutyabff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gauge-48" {...props}></Icon>
