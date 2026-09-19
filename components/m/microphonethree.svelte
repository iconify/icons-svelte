<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-l6l33py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="i-l6l33py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:microphonethree" {...props}></Icon>
