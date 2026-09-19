<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1uq2-bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o1uq2-bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:outdoor" {...props}></Icon>
