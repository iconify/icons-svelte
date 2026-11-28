<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntus0v-mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntus0v-mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-arrow-right" {...props}></Icon>
