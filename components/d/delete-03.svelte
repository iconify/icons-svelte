<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssqmken7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssqmken7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-03" {...props}></Icon>
