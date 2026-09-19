<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtp61qt2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jtp61qt2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:jquery" {...props}></Icon>
