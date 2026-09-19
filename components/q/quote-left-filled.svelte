<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jupx17chv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jupx17chv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-left-filled" {...props}></Icon>
