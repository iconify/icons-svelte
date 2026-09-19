<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/u/u_rm_9byk.css';
import '../../css/z/zt6pghb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsDa0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsDa0)"><path class="u_rm_9byk"/><path class="zt6pghb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:da" {...props}></Icon>
