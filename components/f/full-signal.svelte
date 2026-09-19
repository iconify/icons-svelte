<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyc8edbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyc8edbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:full-signal" {...props}></Icon>
