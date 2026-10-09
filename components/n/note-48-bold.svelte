<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl-eb8nlu.css';
import '../../css/l/l9u6gsyxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dl-eb8nlu"/><path class="l9u6gsyxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:note-48-bold" {...props}></Icon>
