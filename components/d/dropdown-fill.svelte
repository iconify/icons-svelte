<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipymirb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipymirb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dropdown-fill" {...props}></Icon>
