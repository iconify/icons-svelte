<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4m9grbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r4m9grbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plus-circle-fill" {...props}></Icon>
