<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8tz7uh6r.css';
import '../../css/l/lsbxu7b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z8tz7uh6r"/><path class="lsbxu7b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nacelle-48" {...props}></Icon>
