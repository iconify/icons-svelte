<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glki81wsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glki81wsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adobeaudition" {...props}></Icon>
