<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk_1z5bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk_1z5bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reka-ui" {...props}></Icon>
