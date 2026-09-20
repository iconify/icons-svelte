<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/l/ldocbeb6f.css';
import '../../css/a/ao01edcje.css';
import '../../css/p/pag9h1bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="ldocbeb6f"/><path class="ao01edcje"/><path class="pag9h1bav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folders-line" {...props}></Icon>
