<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjjng2bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjjng2bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fite" {...props}></Icon>
