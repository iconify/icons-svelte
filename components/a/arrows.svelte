<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm0gbtz0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pm0gbtz0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrows" {...props}></Icon>
