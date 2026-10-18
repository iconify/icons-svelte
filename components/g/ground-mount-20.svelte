<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2aljf7ie.css';
import '../../css/m/mxxm6-awx.css';
import '../../css/u/uk8t_bc8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o2aljf7ie"/><path class="mxxm6-awx"/><path class="uk8t_bc8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-mount-20" {...props}></Icon>
