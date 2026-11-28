<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw-2bgbkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary sw-2bgbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:moon-duotone" {...props}></Icon>
