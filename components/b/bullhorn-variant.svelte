<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffdp46abo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffdp46abo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bullhorn-variant" {...props}></Icon>
