<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9_h9ldng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s9_h9ldng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-up-alt" {...props}></Icon>
