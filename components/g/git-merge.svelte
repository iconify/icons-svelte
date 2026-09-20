<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xipnj_yzl.css';
import '../../css/j/j4ziy0blu.css';
import '../../css/c/ckfoqpbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xipnj_yzl"/><path class="j4ziy0blu"/><circle class="ckfoqpbve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-merge" {...props}></Icon>
