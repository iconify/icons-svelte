<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ninp90baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ninp90baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:goblet-fill" {...props}></Icon>
