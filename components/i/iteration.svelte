<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k907nmvkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k907nmvkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:iteration" {...props}></Icon>
