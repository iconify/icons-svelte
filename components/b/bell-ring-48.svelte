<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4vq0qbju.css';
import '../../css/y/yxy7ambyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k4vq0qbju"/><path class="yxy7ambyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-ring-48" {...props}></Icon>
