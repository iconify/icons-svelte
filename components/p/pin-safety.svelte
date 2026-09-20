<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/d/da38b_bez.css';
import '../../css/m/ma4nqdb6e.css';
import '../../css/r/rgses48gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="da38b_bez"/><circle class="ma4nqdb6e"/><path class="rgses48gq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:pin-safety" {...props}></Icon>
