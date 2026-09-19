<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp28tacvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp28tacvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:envato" {...props}></Icon>
