<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skc85cbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skc85cbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-star-fill" {...props}></Icon>
