<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g44l4ybwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g44l4ybwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:implant2x-outline" {...props}></Icon>
