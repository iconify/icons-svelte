<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwsnwvbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gwsnwvbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-text-fill" {...props}></Icon>
