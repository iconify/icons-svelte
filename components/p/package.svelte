<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxu7ywznh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxu7ywznh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:package" {...props}></Icon>
