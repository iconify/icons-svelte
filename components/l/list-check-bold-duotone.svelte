<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alwctsldn.css';
import '../../css/r/rjutefbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="alwctsldn"/><path class="rjutefbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-check-bold-duotone" {...props}></Icon>
