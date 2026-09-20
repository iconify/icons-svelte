<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb4-mjx0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb4-mjx0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-slash" {...props}></Icon>
