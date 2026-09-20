<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ellu3obxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ellu3obxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mouse-wireless-solid" {...props}></Icon>
