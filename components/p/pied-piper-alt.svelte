<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx8adxb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1984,"height":1792};
const content = `<path class="xx8adxb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pied-piper-alt" {...props}></Icon>
