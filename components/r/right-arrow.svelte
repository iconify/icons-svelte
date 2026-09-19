<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkgwzph3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkgwzph3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:right-arrow" {...props}></Icon>
