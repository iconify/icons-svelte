<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imvqoebdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="imvqoebdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bookmark" {...props}></Icon>
