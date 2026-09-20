<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl657zm3a.css';
import '../../css/a/a8lg92bba.css';
import '../../css/k/klr2-ud7v.css';
import '../../css/h/hjso-nprq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="sl657zm3a"/><path class="a8lg92bba"/><path class="klr2-ud7v"/><path class="hjso-nprq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:north" {...props}></Icon>
