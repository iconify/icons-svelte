<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrh3eckrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrh3eckrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-arch" {...props}></Icon>
