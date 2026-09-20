<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5lvhug6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w5lvhug6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:control-rewind" {...props}></Icon>
