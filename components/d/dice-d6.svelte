<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2w_62b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c2w_62b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-d6" {...props}></Icon>
