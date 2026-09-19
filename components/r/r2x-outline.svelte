<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae0qi1bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ae0qi1bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:r2x-outline" {...props}></Icon>
