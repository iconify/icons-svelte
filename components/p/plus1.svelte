<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd5vm9b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fd5vm9b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:plus1" {...props}></Icon>
