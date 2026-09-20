<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoikssblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":28};
const content = `<path class="qoikssblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fastwork" {...props}></Icon>
