<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_qfkfbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f_qfkfbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrows-long-right" {...props}></Icon>
