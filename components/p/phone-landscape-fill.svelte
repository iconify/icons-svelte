<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/janlawbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="janlawbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:phone-landscape-fill" {...props}></Icon>
