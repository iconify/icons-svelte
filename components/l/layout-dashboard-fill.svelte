<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8vtk2bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8vtk2bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layout-dashboard-fill" {...props}></Icon>
