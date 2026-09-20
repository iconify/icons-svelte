<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h7el7udao.css';
import '../../css/g/g017pksnm.css';
import '../../css/e/eg2568bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h7el7udao"/><path class="g017pksnm"/><circle class="eg2568bgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:file-clock" {...props}></Icon>
