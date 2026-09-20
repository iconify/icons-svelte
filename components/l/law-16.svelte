<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2n_s1h7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l2n_s1h7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:law-16" {...props}></Icon>
