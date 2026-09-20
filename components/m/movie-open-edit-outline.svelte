<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3d5edgbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3d5edgbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-open-edit-outline" {...props}></Icon>
