<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/job_fgb5d.css';
import '../../css/e/es4tnviht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="job_fgb5d"/><path class="es4tnviht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pallet-20" {...props}></Icon>
