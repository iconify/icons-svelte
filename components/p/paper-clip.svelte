<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u48w4hbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u48w4hbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paper-clip" {...props}></Icon>
