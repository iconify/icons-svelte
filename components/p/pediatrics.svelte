<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n570r8b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n570r8b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pediatrics" {...props}></Icon>
