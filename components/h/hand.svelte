<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vppex3q9g.css';
import '../../css/o/oerg6hb2z.css';
import '../../css/o/orgv1obkj.css';
import '../../css/a/a8f4nq6ud.css';
import '../../css/f/f9z9tgbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vppex3q9g wm-k"/><path class="oerg6hb2z wm-k"/><path class="orgv1obkj wm-k"/><path class="a8f4nq6ud wm-shine"/><path class="f9z9tgbch wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-anime:hand" {...props}></Icon>
