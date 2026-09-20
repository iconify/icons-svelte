<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bay1nz_kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bay1nz_kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:memories-line" {...props}></Icon>
