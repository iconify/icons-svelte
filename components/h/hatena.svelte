<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd7rvbbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":819,"height":681};
const content = `<path class="gd7rvbbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:hatena" {...props}></Icon>
