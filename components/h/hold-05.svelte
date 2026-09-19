<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_tqlwhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za_tqlwhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hold-05" {...props}></Icon>
