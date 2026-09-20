<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqiz-vagk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lqiz-vagk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:login" {...props}></Icon>
