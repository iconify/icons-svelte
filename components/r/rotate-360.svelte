<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix8qmsm_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix8qmsm_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-360" {...props}></Icon>
