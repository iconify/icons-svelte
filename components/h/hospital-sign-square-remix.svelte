<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8_rbj_tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w8_rbj_tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:hospital-sign-square-remix" {...props}></Icon>
