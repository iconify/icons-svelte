<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cem9-c3jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cem9-c3jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-down-linear" {...props}></Icon>
