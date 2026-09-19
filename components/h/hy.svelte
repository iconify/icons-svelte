<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/h/hr2vw8qnh.css';
import '../../css/e/efq5ztb1c.css';
import '../../css/n/ncqlw91-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsHy0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsHy0)"><path class="hr2vw8qnh"/><path class="efq5ztb1c"/><path class="ncqlw91-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:hy" {...props}></Icon>
