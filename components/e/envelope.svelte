<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afdq6s1fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afdq6s1fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:envelope" {...props}></Icon>
