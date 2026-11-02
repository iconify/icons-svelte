<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gckeohb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gckeohb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lens-concave-fill" {...props}></Icon>
