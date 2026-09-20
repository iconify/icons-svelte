<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt50purwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nt50purwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pen" {...props}></Icon>
