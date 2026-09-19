<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgrmmlbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dgrmmlbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:animal-spider2x-outline" {...props}></Icon>
