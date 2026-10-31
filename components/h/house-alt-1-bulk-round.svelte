<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb0burbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb0burbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-1-bulk-round" {...props}></Icon>
