<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hln_rnjqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hln_rnjqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:rotate-left-solid" {...props}></Icon>
