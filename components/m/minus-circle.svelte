<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csr1j5bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="csr1j5bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:minus-circle" {...props}></Icon>
