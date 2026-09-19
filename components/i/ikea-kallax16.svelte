<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj90sf8ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj90sf8ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-kallax16" {...props}></Icon>
