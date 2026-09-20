<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5uvpgbez.css';
import '../../css/h/h_pt1abna.css';
import '../../css/h/hlibxwb-i.css';
import '../../css/e/e4zfowz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="k5uvpgbez"/><path class="h_pt1abna"/><path class="hlibxwb-i"/><path class="e4zfowz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:libra" {...props}></Icon>
