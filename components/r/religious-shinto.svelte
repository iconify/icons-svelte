<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-4cpzbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l-4cpzbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:religious-shinto" {...props}></Icon>
