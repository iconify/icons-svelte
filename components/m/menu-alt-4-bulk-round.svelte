<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuz-0actz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuz-0actz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-4-bulk-round" {...props}></Icon>
