<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvvlq2bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pvvlq2bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleg" {...props}></Icon>
