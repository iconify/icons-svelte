<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udpmr1b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="udpmr1b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:increase-indent-hanging" {...props}></Icon>
