<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibmsagb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ibmsagb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-image" {...props}></Icon>
