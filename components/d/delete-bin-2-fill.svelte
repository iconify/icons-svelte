<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cszim8v5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cszim8v5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-bin-2-fill" {...props}></Icon>
