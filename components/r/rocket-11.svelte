<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asp71d7jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="asp71d7jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:rocket-11" {...props}></Icon>
