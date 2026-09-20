<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf_jb02lk.css';
import '../../css/v/v3xgw3bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wf_jb02lk"/><path class="v3xgw3bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-ringing-16" {...props}></Icon>
