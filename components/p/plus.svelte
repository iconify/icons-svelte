<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4e6zl6iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y4e6zl6iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:plus" {...props}></Icon>
