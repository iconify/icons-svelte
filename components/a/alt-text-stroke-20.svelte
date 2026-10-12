<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfe6msdjj.css';
import '../../css/c/cm27p2byo.css';
import '../../css/z/zfvicoeco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cfe6msdjj"/><path class="cm27p2byo"/><path class="zfvicoeco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alt-text-stroke-20" {...props}></Icon>
