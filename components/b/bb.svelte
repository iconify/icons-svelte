<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/avvfdb35i.css';
import '../../css/b/bgs-3wb5e.css';
import '../../css/z/zrjmoujkm.css';
import '../../css/k/k15qmubyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="avvfdb35i"/><path class="bgs-3wb5e"/><path class="zrjmoujkm"/><path class="k15qmubyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:bb" {...props}></Icon>
