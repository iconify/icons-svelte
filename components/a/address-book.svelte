<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hegyceb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hegyceb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:address-book" {...props}></Icon>
