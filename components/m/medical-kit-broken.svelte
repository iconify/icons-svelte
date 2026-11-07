<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/ebr-_j5mg.css';
import '../../css/h/hq-5njbjh.css';
import '../../css/k/k8us2bvxz.css';
import '../../css/u/ukvmc8bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ebr-_j5mg"/><path class="hq-5njbjh"/><path class="k8us2bvxz"/><circle class="ukvmc8bfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medical-kit-broken" {...props}></Icon>
