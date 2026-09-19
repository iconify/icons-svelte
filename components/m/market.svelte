<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-nwy9zre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="c-nwy9zre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:market" {...props}></Icon>
