<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nhrqm3bvg.css';
import '../../css/q/qh4mjcc9l.css';
import '../../css/t/tcfkbc24e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nhrqm3bvg"/><path class="qh4mjcc9l"/><path class="tcfkbc24e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-abstract" {...props}></Icon>
