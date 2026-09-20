<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6b8a2bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h6b8a2bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-cursor-move-solid" {...props}></Icon>
