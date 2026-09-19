<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daw-8pbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daw-8pbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:crown-filled" {...props}></Icon>
