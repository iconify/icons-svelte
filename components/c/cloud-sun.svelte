<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da6q-edbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da6q-edbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-sun" {...props}></Icon>
