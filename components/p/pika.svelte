<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xov_0wbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xov_0wbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pika" {...props}></Icon>
