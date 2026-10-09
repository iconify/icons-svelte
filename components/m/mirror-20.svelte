<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utpm0pbkq.css';
import '../../css/g/gl28njbdi.css';
import '../../css/m/m-7py9b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="utpm0pbkq"/><path class="gl28njbdi"/><path class="m-7py9b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mirror-20" {...props}></Icon>
