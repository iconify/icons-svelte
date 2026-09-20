<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmgqnccqy.css';
import '../../css/p/pnlwn_bgq.css';
import '../../css/e/e_h1d4ywv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmgqnccqy"/><path class="pnlwn_bgq"/><path class="e_h1d4ywv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ist" {...props}></Icon>
