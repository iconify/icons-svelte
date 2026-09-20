<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luh_gnorz.css';
import '../../css/o/o740cbcaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="luh_gnorz"/><path class="o740cbcaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:alarm" {...props}></Icon>
