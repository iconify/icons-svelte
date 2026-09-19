<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnar-68-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnar-68-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bookmark-empty" {...props}></Icon>
