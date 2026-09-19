<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5l6xgz1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="u5l6xgz1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:down-long" {...props}></Icon>
