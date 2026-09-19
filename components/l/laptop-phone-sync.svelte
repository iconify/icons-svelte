<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tue_7dbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tue_7dbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:laptop-phone-sync" {...props}></Icon>
