<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozhwhlihc.css';
import '../../css/k/kr4l01btv.css';
import '../../css/n/nrn-6ibeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ozhwhlihc"/><path class="kr4l01btv"/><path class="nrn-6ibeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lamp-20" {...props}></Icon>
