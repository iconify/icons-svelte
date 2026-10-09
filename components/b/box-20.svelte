<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqn8gqb4e.css';
import '../../css/m/m-ue7vdss.css';
import '../../css/u/u_-d_vaka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hqn8gqb4e"/><path class="m-ue7vdss"/><path class="u_-d_vaka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-20" {...props}></Icon>
