<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2nmz2bly.css';
import '../../css/s/sosvirbjg.css';
import '../../css/p/pu92vnbag.css';
import '../../css/s/sc8qubbfy.css';
import '../../css/f/fbwghxbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<g class="ft5dv1b6b"><path class="b2nmz2bly"/><path clip-rule="evenodd" class="sosvirbjg"/><path clip-rule="evenodd" class="pu92vnbag"/><path clip-rule="evenodd" class="sc8qubbfy"/><path clip-rule="evenodd" class="fbwghxbxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:peerlist" {...props}></Icon>
