<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elffk3bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elffk3bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pen2-filled" {...props}></Icon>
