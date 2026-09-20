<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueax62bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueax62bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jbl" {...props}></Icon>
