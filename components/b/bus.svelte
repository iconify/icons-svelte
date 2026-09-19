<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrt54buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrt54buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bus" {...props}></Icon>
