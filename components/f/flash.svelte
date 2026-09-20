<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufmi-ibuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmi-ibuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flash" {...props}></Icon>
