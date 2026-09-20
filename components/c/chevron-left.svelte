<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1eqt2byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":16};
const content = `<path class="k1eqt2byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-left" {...props}></Icon>
