<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knjor4pcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knjor4pcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:fast-forward" {...props}></Icon>
