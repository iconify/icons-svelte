<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jslnalb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jslnalb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:group-discussion-meeting-outline" {...props}></Icon>
