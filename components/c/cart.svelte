<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyih9acsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gyih9acsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cart" {...props}></Icon>
