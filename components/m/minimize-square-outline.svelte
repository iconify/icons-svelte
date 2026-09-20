<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyhblzb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lyhblzb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-outline" {...props}></Icon>
