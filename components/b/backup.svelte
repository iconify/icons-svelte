<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9j6bob4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9j6bob4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:backup" {...props}></Icon>
