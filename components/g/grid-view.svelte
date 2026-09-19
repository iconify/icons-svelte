<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0jrx045d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0jrx045d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:grid-view" {...props}></Icon>
