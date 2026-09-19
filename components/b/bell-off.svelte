<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqz_3cskk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqz_3cskk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bell-off" {...props}></Icon>
