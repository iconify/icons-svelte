<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt-53grje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt-53grje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-cancel-outline" {...props}></Icon>
