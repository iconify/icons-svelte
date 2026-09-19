<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjhq55beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="bjhq55beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:gear" {...props}></Icon>
