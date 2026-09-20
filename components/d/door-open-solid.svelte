<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btudybbmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="btudybbmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:door-open-solid" {...props}></Icon>
