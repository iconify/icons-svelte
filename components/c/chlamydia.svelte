<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl834o1cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nl834o1cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chlamydia" {...props}></Icon>
