<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaxcsz8rc.css';
import '../../css/r/rzy0o9f7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aaxcsz8rc"/><path class="rzy0o9f7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cheese-48" {...props}></Icon>
