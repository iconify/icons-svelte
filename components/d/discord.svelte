<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy2xg2bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy2xg2bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:discord" {...props}></Icon>
