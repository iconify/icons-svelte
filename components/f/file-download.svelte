<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muo_u7brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muo_u7brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-download" {...props}></Icon>
