<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrei6fbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrei6fbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hearthisdotat" {...props}></Icon>
