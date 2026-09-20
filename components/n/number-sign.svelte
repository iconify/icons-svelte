<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or1wnh-nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="or1wnh-nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:number-sign" {...props}></Icon>
