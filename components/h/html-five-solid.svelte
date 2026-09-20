<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf0fngu7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sf0fngu7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:html-five-solid" {...props}></Icon>
