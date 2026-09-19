<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c083e7b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c083e7b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:font-size" {...props}></Icon>
