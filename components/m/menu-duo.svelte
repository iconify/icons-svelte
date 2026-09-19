<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdc5flbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdc5flbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:menu-duo" {...props}></Icon>
