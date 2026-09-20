<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xznamb27i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xznamb27i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kibana" {...props}></Icon>
