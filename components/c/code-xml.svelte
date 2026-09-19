<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6e5m8brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6e5m8brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:code-xml" {...props}></Icon>
