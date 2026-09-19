<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spvo8abkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="spvo8abkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bad" {...props}></Icon>
