<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzssj_eru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzssj_eru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-chart-line-solid" {...props}></Icon>
