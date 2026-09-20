<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp6iuvngt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp6iuvngt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bookmyshow" {...props}></Icon>
