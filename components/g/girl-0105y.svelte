<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud4eghbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ud4eghbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:girl-0105y" {...props}></Icon>
