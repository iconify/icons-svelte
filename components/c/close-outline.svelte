<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch2o2yfcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch2o2yfcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:close-outline" {...props}></Icon>
