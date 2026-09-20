<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_s-y0-hq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_s-y0-hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dell-fill" {...props}></Icon>
