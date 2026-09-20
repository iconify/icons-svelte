<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjsj_ebfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjsj_ebfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-gantt" {...props}></Icon>
