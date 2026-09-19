<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs5ksoa2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs5ksoa2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:money" {...props}></Icon>
