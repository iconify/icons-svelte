<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1j9xnt4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1j9xnt4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:printer" {...props}></Icon>
