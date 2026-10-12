<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwnut8bui.css';
import '../../css/t/tag_xcyrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xwnut8bui"/><path class="tag_xcyrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gearbox-48" {...props}></Icon>
