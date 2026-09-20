<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oldue7tnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oldue7tnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notification" {...props}></Icon>
