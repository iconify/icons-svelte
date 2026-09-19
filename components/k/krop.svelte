<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2skmjbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":448};
const content = `<path class="g2skmjbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:krop" {...props}></Icon>
