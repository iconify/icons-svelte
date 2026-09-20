<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lupkgv2gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lupkgv2gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iconfinder" {...props}></Icon>
