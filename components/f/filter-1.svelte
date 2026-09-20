<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owioo-z8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owioo-z8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:filter-1" {...props}></Icon>
