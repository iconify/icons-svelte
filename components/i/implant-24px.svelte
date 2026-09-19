<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so_se7bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so_se7bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:implant-24px" {...props}></Icon>
