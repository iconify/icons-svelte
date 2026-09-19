<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcfqgs_zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":580,"height":850};
const content = `<path class="rcfqgs_zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:bucket" {...props}></Icon>
