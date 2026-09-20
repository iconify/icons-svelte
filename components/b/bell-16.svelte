<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g23khybbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g23khybbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bell-16" {...props}></Icon>
