<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae1tb3ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ae1tb3ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-right" {...props}></Icon>
