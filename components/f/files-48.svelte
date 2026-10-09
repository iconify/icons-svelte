<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w18tredqi.css';
import '../../css/a/autp9p4ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w18tredqi"/><path class="autp9p4ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:files-48" {...props}></Icon>
