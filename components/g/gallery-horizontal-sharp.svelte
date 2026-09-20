<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yox_8jbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yox_8jbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-horizontal-sharp" {...props}></Icon>
