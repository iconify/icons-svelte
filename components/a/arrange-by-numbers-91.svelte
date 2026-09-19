<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxpmqvbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxpmqvbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrange-by-numbers-91" {...props}></Icon>
