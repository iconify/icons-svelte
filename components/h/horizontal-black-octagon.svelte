<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqualhbgp.css';
import '../../css/v/v_pt9ob9w.css';
import '../../css/d/dcu62ebsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="gqualhbgp"/><path class="v_pt9ob9w"/><path class="dcu62ebsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:horizontal-black-octagon" {...props}></Icon>
