<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsbzb68xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsbzb68xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-black-white" {...props}></Icon>
