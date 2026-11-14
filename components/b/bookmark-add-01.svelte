<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eadr-pbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eadr-pbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-add-01" {...props}></Icon>
