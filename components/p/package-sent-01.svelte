<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbwr5ownf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbwr5ownf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-sent-01" {...props}></Icon>
