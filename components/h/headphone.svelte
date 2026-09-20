<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-0lbqb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k-0lbqb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:headphone" {...props}></Icon>
