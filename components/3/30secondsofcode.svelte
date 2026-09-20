<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9ntl4oxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9ntl4oxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:30secondsofcode" {...props}></Icon>
