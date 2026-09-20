<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0ue3pb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0ue3pb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:palantir" {...props}></Icon>
