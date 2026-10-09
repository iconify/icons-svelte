<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v71jzsb3t.css';
import '../../css/i/ilg_98b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v71jzsb3t"/><path class="ilg_98b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plus-48-bold" {...props}></Icon>
