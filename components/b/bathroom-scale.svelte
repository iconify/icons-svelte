<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8t-mhbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b8t-mhbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bathroom-scale" {...props}></Icon>
