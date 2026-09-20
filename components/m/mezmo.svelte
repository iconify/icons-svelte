<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra4ievf3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4ievf3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mezmo" {...props}></Icon>
