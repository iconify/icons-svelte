<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlsx0d_2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="vlsx0d_2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pinterest-square" {...props}></Icon>
