<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxka6984l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxka6984l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bittorrent" {...props}></Icon>
