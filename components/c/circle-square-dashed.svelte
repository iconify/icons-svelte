<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnnb155mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnnb155mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-square-dashed" {...props}></Icon>
