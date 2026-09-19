<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaac_sbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qaac_sbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-one" {...props}></Icon>
