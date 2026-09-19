<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqt-14zzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gqt-14zzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cast2x-outline" {...props}></Icon>
