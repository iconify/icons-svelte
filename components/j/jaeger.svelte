<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb-u1wi3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-u1wi3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jaeger" {...props}></Icon>
