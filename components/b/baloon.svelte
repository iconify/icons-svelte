<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlp5gb8zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="tlp5gb8zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:baloon" {...props}></Icon>
