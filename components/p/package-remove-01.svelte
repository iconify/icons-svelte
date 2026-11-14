<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0hn8zakz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0hn8zakz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-remove-01" {...props}></Icon>
