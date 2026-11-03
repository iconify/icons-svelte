<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9_ihwbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9_ihwbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:anchor" {...props}></Icon>
