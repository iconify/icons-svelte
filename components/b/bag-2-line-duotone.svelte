<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o4ffp8zxl.css';
import '../../css/p/pv5uptb2w.css';
import '../../css/k/k8yjj9bgj.css';
import '../../css/m/mw42pob4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o4ffp8zxl"/><path class="pv5uptb2w"/><path class="k8yjj9bgj"/><path class="mw42pob4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-2-line-duotone" {...props}></Icon>
