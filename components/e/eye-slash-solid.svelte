<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8pmzds9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b8pmzds9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:eye-slash-solid" {...props}></Icon>
