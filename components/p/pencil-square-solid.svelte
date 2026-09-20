<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9y34yaiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="b9y34yaiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pencil-square-solid" {...props}></Icon>
