<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd3383bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nd3383bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:money-bill-alt" {...props}></Icon>
