<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1qflhkfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="x1qflhkfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:list-numbered" {...props}></Icon>
