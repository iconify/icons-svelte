<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-j_9y_2k.css';
import '../../css/n/nsncu0byu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w-j_9y_2k"/><path class="nsncu0byu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kettle-20-bold" {...props}></Icon>
