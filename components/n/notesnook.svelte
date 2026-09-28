<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxojr_bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxojr_bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:notesnook" {...props}></Icon>
