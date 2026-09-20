<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmfvf21cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vmfvf21cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:align-right-flat" {...props}></Icon>
