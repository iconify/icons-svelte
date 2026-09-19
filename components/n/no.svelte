<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1iq95bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z1iq95bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:no" {...props}></Icon>
