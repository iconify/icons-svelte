<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-_12jovm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="i-_12jovm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cssthree" {...props}></Icon>
