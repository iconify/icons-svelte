<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2o-2zxot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="l2o-2zxot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:helicopter" {...props}></Icon>
