<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adx82e9yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="adx82e9yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-watch-time" {...props}></Icon>
