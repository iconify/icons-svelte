<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cvbiv5ecy.css';
import '../../css/n/nkd99mgmf.css';
import '../../css/o/olxh2rbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="cvbiv5ecy"/><path class="nkd99mgmf"/><path class="olxh2rbbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:remind" {...props}></Icon>
