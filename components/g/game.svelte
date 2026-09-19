<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvqwzbcbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":669};
const content = `<path class="yvqwzbcbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:game" {...props}></Icon>
