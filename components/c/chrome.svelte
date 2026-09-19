<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj3mtbc7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="dj3mtbc7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:chrome" {...props}></Icon>
