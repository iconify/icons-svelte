<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biji12x1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="biji12x1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:gist" {...props}></Icon>
