<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dus1nvzmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dus1nvzmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:revanced" {...props}></Icon>
