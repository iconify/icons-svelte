<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un83tfh1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un83tfh1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bell" {...props}></Icon>
