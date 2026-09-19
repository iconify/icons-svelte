<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezlrxrblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1856,"height":1408};
const content = `<path class="ezlrxrblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:coffee" {...props}></Icon>
