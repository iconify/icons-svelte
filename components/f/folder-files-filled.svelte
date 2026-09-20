<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ipm975hdc.css';
import '../../css/k/kxq-picmp.css';
import '../../css/q/qqwtvdb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ipm975hdc"/><path clip-rule="evenodd" class="kxq-picmp"/><path class="qqwtvdb2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-files-filled" {...props}></Icon>
