<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2uhb_-xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2uhb_-xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-duotone" {...props}></Icon>
