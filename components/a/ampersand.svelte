<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd1d7sb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qd1d7sb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ampersand" {...props}></Icon>
