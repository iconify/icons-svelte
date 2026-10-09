<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juz-jcb_p.css';
import '../../css/v/vbotk2bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="juz-jcb_p"/><path class="vbotk2bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noise-reduction-20" {...props}></Icon>
