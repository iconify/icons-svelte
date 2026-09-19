<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxqxg_35p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxqxg_35p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-bold" {...props}></Icon>
