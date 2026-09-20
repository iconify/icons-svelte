<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/banr10v6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="banr10v6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:eye-closed-outline" {...props}></Icon>
