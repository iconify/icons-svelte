<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8d96qbpq.css';
import '../../css/v/v5jciabna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8d96qbpq"/><path class="v5jciabna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbells-bold-duotone" {...props}></Icon>
