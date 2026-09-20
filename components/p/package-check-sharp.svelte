<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei-yqccis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei-yqccis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-check-sharp" {...props}></Icon>
