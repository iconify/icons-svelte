<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbn8jqf1h.css';
import '../../css/b/b0cn2mb5s.css';
import '../../css/c/ct59a3bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fbn8jqf1h"/><path class="b0cn2mb5s"/><path class="ct59a3bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:police-station-20-bold" {...props}></Icon>
