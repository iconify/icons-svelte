<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl_3kfblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sl_3kfblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-library-16-solid" {...props}></Icon>
