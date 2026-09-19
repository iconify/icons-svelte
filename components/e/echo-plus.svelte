<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzfj7k4kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzfj7k4kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:echo-plus" {...props}></Icon>
