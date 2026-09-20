<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzz5zzkqw.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/w/wsi5a16wd.css';
import '../../css/g/gus1k0b4h.css';
import '../../css/r/rb9bmbcgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hzz5zzkqw"/><g class="sxsjrzbyv"><path class="wsi5a16wd"/><g clip-rule="evenodd"><path class="gus1k0b4h"/><path class="rb9bmbcgk"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dotnet" {...props}></Icon>
