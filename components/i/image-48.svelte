<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rthtgrrbd.css';
import '../../css/r/rbqngdcgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rthtgrrbd"/><path class="rbqngdcgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-48" {...props}></Icon>
