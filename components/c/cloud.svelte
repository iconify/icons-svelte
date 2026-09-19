<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saejn7btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="saejn7btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloud" {...props}></Icon>
