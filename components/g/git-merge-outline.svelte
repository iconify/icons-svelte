<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgrlpfb5w.css';
import '../../css/n/nm7yi4b_v.css';
import '../../css/n/npaoi6s8i.css';
import '../../css/e/ezv6ukqwd.css';
import '../../css/f/fi82jxbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xgrlpfb5w"/><circle class="nm7yi4b_v"/><path class="npaoi6s8i"/><circle class="ezv6ukqwd"/><path class="fi82jxbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-merge-outline" {...props}></Icon>
