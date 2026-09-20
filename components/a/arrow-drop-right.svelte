<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn9pn5b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn9pn5b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-drop-right" {...props}></Icon>
