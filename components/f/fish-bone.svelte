<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mscfj9vem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mscfj9vem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fish-bone" {...props}></Icon>
