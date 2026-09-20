<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhnybhx3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhnybhx3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-2-outline" {...props}></Icon>
