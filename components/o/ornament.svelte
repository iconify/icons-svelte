<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtm9d9bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtm9d9bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ornament" {...props}></Icon>
