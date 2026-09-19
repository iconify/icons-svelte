<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h-n7zzbgh.css';
import '../../css/m/mlrpppb7t.css';
import '../../css/v/vbwyi6mgn.css';
import '../../css/e/etcqljbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="h-n7zzbgh"/><path class="mlrpppb7t"/><path class="vbwyi6mgn"/><path class="etcqljbzx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:boxing-glove" {...props}></Icon>
