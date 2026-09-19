<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b89_mpbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1792};
const content = `<path class="b89_mpbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gears" {...props}></Icon>
