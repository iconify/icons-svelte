<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_fat9ykp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_fat9ykp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-filter-solid" {...props}></Icon>
