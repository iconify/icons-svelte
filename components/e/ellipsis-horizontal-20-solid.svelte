<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui15hlbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ui15hlbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal-20-solid" {...props}></Icon>
