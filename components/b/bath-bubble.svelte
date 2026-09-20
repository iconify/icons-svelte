<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/puhw2wz1p.css';
import '../../css/j/jf4vsjl9n.css';
import '../../css/x/xd5om9bvr.css';
import '../../css/l/l8vwp4bnt.css';
import '../../css/e/e6rcat6vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="puhw2wz1p"/><circle class="jf4vsjl9n"/><circle class="xd5om9bvr"/><path class="l8vwp4bnt"/><path class="e6rcat6vq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:bath-bubble" {...props}></Icon>
