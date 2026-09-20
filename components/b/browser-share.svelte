<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uijg__bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uijg__bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:browser-share" {...props}></Icon>
