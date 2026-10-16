<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbw01lbki.css';
import '../../css/n/n2ifbxbof.css';
import '../../css/e/ecag-tbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kbw01lbki"/><path class="n2ifbxbof"/><path class="ecag-tbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ceiling-light-20" {...props}></Icon>
