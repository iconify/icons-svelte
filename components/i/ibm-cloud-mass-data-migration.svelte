<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye20y-oru.css';
import '../../css/m/mnqs348qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ye20y-oru"/><path class="mnqs348qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-mass-data-migration" {...props}></Icon>
