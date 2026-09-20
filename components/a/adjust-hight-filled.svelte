<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_5_ixbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x_5_ixbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:adjust-hight-filled" {...props}></Icon>
