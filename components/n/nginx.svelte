<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za-3b2xgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="za-3b2xgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nginx" {...props}></Icon>
