<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym9ybcc6l.css';
import '../../css/x/xo930qbei.css';
import '../../css/e/e4ja3lute.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ym9ybcc6l"/><path class="xo930qbei"/><path class="e4ja3lute"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:person-walking-48" {...props}></Icon>
