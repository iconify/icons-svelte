<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enw5fd1wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="enw5fd1wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:nightclub" {...props}></Icon>
