<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu7qf6bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="lu7qf6bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:menu" {...props}></Icon>
