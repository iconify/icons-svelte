<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb7k1eeah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="qb7k1eeah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-up-down" {...props}></Icon>
