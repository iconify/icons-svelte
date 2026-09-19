<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv_df9bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mv_df9bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:page-right-solid" {...props}></Icon>
