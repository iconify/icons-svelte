<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bl912rbdb.css';
import '../../css/h/hduycmbms.css';
import '../../css/e/e84_jcm9v.css';
import '../../css/b/b3a0n5bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="bl912rbdb"/><path class="hduycmbms"/><path class="e84_jcm9v"/><path class="b3a0n5bzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:clapper-board" {...props}></Icon>
