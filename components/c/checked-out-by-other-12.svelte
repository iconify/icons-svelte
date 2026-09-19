<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-jh1-4ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u-jh1-4ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:checked-out-by-other-12" {...props}></Icon>
