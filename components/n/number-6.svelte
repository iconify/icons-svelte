<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv78vfhwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv78vfhwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:number-6" {...props}></Icon>
