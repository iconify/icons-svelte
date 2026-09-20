<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn85zbh0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="fn85zbh0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plus" {...props}></Icon>
