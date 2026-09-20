<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdo4uxbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdo4uxbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-nifi" {...props}></Icon>
