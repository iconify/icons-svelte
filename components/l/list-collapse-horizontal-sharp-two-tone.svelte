<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t361nh1vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t361nh1vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-collapse-horizontal-sharp-two-tone" {...props}></Icon>
