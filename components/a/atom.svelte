<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjhi1nb3h.css';
import '../../css/v/vtl91obdm.css';
import '../../css/b/bwrwnlb7x.css';
import '../../css/c/cnrul6y8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjhi1nb3h wm-k"/><path class="vtl91obdm wm-k"/><path class="bwrwnlb7x wm-k"/><path class="cnrul6y8o wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:atom" {...props}></Icon>
