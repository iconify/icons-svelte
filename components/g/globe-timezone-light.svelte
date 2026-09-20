<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei6395-9p.css';
import '../../css/e/ekf9xwedv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei6395-9p"/><path class="ekf9xwedv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:globe-timezone-light" {...props}></Icon>
