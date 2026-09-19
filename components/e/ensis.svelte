<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88pj6-vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88pj6-vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ensis" {...props}></Icon>
