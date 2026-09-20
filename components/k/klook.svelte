<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6x368b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6x368b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:klook" {...props}></Icon>
