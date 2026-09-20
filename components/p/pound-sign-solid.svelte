<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqj_exb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iqj_exb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pound-sign-solid" {...props}></Icon>
