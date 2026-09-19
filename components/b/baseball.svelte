<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g62_debmy.css';
import '../../css/g/gx4l6kh5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g62_debmy"/><path class="gx4l6kh5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:baseball" {...props}></Icon>
