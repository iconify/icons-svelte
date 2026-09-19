<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jayb1w7jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jayb1w7jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-square" {...props}></Icon>
