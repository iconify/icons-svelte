<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbn2wh0re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbn2wh0re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ichi" {...props}></Icon>
