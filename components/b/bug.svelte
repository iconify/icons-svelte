<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9_-o9owr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":496};
const content = `<path class="o9_-o9owr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bug" {...props}></Icon>
