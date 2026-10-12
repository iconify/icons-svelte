<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swzmu3awr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swzmu3awr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:between-horizontal-end-filled" {...props}></Icon>
