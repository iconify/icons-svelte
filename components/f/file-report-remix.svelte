<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg1szrr6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dg1szrr6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:file-report-remix" {...props}></Icon>
