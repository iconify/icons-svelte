<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpjhhactr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gpjhhactr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:number-circle-fill" {...props}></Icon>
