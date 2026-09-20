<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt9wvpbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jt9wvpbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:laugh-wink-solid" {...props}></Icon>
