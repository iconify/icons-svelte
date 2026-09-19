<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-iie2b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k-iie2b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mergecells" {...props}></Icon>
