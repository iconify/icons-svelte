<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfxchrbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfxchrbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-clock" {...props}></Icon>
