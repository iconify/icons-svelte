<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk1y5c0sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk1y5c0sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-solid" {...props}></Icon>
