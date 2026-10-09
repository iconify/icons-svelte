<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilg_98b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ilg_98b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minus-48-bold" {...props}></Icon>
