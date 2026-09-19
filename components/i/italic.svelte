<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeee4ly_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeee4ly_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:italic" {...props}></Icon>
