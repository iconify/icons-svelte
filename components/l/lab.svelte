<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmbc4zpnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="kmbc4zpnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:lab" {...props}></Icon>
