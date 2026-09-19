<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-3m8fbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b-3m8fbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-minus-fill" {...props}></Icon>
