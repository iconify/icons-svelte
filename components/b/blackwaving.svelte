<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ichh20b6b.css';
import '../../css/f/f4xgot2-t.css';
import '../../css/s/sshvt2bwd.css';
import '../../css/d/dmmpmib0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ichh20b6b"/><path class="f4xgot2-t"/><path class="sshvt2bwd"/><path class="dmmpmib0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackwaving" {...props}></Icon>
