<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikxnezhma.css';
import '../../css/a/ao3xg6lae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ikxnezhma"/><path class="ao3xg6lae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-bold-duotone" {...props}></Icon>
