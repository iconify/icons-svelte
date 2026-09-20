<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwl_c-0if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mwl_c-0if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pool-ladder-remix" {...props}></Icon>
