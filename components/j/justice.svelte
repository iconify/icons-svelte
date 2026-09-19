<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf3a7wbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sf3a7wbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:justice" {...props}></Icon>
