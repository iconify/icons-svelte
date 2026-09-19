<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmo02zb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nmo02zb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:azure" {...props}></Icon>
