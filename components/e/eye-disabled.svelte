<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9j4rgb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9j4rgb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:eye-disabled" {...props}></Icon>
