<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjiknzb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fjiknzb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:envolope-letter" {...props}></Icon>
