<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozsgqjbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozsgqjbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left2" {...props}></Icon>
