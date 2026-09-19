<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxbq9ib_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxbq9ib_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-analytics" {...props}></Icon>
