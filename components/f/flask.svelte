<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgay69b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1024};
const content = `<path class="sgay69b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flask" {...props}></Icon>
