<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qh68rnblk.css';
import '../../css/g/g45mtmdnj.css';
import '../../css/t/tcccckbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qh68rnblk"/><path class="g45mtmdnj"/><path class="tcccckbck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:like-duotone" {...props}></Icon>
