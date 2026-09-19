<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwj-tdbmb.css';
import '../../css/k/k4o7aepui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwj-tdbmb"/><path class="k4o7aepui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:archive-in" {...props}></Icon>
