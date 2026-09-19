<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5e0utiaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f5e0utiaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ear-outline" {...props}></Icon>
