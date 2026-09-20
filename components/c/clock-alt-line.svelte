<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzdsy5qft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzdsy5qft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clock-alt-line" {...props}></Icon>
