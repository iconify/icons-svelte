<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkhc6obyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="wkhc6obyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-up-a-z" {...props}></Icon>
