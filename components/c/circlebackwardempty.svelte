<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c46figbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c46figbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlebackwardempty" {...props}></Icon>
