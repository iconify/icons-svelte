<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stvzi0b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="stvzi0b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:octagon" {...props}></Icon>
