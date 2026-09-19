<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9z807bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":640};
const content = `<path class="m9z807bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chevrondown" {...props}></Icon>
