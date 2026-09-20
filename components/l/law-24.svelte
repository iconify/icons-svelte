<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsot7ab7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsot7ab7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:law-24" {...props}></Icon>
