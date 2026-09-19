<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp5ecabad.css';
import '../../css/y/ydng6ub1v.css';
import '../../css/o/omk7q06vg.css';
import '../../css/c/ceddezowq.css';
import '../../css/g/gxa31hbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp5ecabad"/><path class="ydng6ub1v"/><path class="omk7q06vg"/><path class="ceddezowq"/><path class="gxa31hbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-ids" {...props}></Icon>
