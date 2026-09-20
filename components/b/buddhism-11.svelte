<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-rxtsdyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="n-rxtsdyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:buddhism-11" {...props}></Icon>
