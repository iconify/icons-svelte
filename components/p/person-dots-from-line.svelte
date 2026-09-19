<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw39xqz4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="yw39xqz4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-dots-from-line" {...props}></Icon>
