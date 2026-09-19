<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehrol8p9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ehrol8p9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-alt-circle-right" {...props}></Icon>
