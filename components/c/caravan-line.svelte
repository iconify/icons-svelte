<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk5libcxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk5libcxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:caravan-line" {...props}></Icon>
