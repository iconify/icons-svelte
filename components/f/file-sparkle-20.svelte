<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szahujb-p.css';
import '../../css/s/sm8tyk6uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="sm8tyk6uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-sparkle-20" {...props}></Icon>
