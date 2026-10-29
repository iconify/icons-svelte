<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtqntyqlm.css';
import '../../css/j/jcqvt8bwl.css';
import '../../css/m/mmwz_gbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtqntyqlm wm-shadow"/><path class="jcqvt8bwl wm-k"/><path class="mmwz_gbga wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:arrow-up" {...props}></Icon>
