<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlqpo7b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tlqpo7b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bucket-fill" {...props}></Icon>
