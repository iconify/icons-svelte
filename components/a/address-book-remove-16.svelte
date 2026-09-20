<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx1ebmbsz.css';
import '../../css/c/cic6sccqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kx1ebmbsz"/><path class="cic6sccqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:address-book-remove-16" {...props}></Icon>
