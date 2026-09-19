<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge5bw_bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ge5bw_bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-circle" {...props}></Icon>
