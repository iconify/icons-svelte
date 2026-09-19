<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4_1llqee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s4_1llqee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-narrow-right" {...props}></Icon>
