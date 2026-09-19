<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdv30hu3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":959};
const content = `<path class="tdv30hu3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:diefour" {...props}></Icon>
