<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf40rc43n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf40rc43n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-cancel" {...props}></Icon>
