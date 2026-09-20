<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhmm7i-2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhmm7i-2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:abbott" {...props}></Icon>
