<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crs_a_bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crs_a_bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:database-x-solid" {...props}></Icon>
