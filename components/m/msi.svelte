<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeardub_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeardub_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:msi" {...props}></Icon>
