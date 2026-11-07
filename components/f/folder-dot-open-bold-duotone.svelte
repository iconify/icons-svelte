<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-xvykjbc.css';
import '../../css/a/atm69obhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-xvykjbc"/><path class="atm69obhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-open-bold-duotone" {...props}></Icon>
