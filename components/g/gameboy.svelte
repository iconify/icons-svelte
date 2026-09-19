<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m42zp2umy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="m42zp2umy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:gameboy" {...props}></Icon>
