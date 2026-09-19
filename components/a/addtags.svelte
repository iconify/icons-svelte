<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw8djlhdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qw8djlhdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:addtags" {...props}></Icon>
