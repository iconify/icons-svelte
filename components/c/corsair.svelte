<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1v1xeb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1v1xeb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:corsair" {...props}></Icon>
