<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arbl_acfa.css';
import '../../css/j/jjurvxulj.css';
import '../../css/w/w3lw55b-f.css';
import '../../css/i/iii9vdbnp.css';
import '../../css/c/c2g-pd3xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="arbl_acfa"/><path class="jjurvxulj"/><path class="w3lw55b-f"/><path class="iii9vdbnp"/><path class="c2g-pd3xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-plugged-48-bold" {...props}></Icon>
