<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8h1-6bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q8h1-6bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:foot" {...props}></Icon>
