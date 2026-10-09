<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilg_98b5z.css';
import '../../css/r/r9g8q-bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ilg_98b5z"/><path class="r9g8q-bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-48-bold" {...props}></Icon>
