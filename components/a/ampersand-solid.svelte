<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lin6cdbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lin6cdbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ampersand-solid" {...props}></Icon>
