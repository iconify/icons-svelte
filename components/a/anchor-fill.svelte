<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjbyqm_dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjbyqm_dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anchor-fill" {...props}></Icon>
