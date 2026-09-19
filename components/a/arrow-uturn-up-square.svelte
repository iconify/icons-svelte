<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt8f_wtrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rt8f_wtrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-up-square" {...props}></Icon>
