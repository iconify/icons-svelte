<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm_kkbuq.css';
import '../../css/h/hffq3ijlx.css';
import '../../css/t/tjw051bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adm_kkbuq"/><path class="hffq3ijlx"/><path clip-rule="evenodd" class="tjw051bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:file-plus-circle" {...props}></Icon>
