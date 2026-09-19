<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5ld2picv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="s5ld2picv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:knife" {...props}></Icon>
