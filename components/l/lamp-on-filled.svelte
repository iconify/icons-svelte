<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft7_yqb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7_yqb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lamp-on-filled" {...props}></Icon>
