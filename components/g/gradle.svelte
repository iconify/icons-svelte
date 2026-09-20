<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqgw9ccji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqgw9ccji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gradle" {...props}></Icon>
