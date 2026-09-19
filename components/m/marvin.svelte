<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_i7odbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1026};
const content = `<path class="f_i7odbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:marvin" {...props}></Icon>
