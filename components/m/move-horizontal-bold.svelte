<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et0o79h9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et0o79h9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-horizontal-bold" {...props}></Icon>
