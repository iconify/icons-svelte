<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtbzzkg9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wtbzzkg9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:racetrack-horse" {...props}></Icon>
