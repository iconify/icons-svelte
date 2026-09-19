<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugt05jc1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ugt05jc1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:photo-2-fill" {...props}></Icon>
