<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh3jonbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":897,"height":1024};
const content = `<path class="wh3jonbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pagebreak" {...props}></Icon>
