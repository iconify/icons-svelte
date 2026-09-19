<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu5p79zwm.css';
import '../../css/l/l34qd19yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bu5p79zwm"/><path class="l34qd19yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:radiation" {...props}></Icon>
