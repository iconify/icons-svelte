<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpf16_b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tpf16_b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:lock" {...props}></Icon>
