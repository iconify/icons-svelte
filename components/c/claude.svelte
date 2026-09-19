<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijfone47c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ijfone47c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:claude" {...props}></Icon>
