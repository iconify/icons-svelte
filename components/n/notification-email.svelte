<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amdrchs6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="amdrchs6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:notification-email" {...props}></Icon>
