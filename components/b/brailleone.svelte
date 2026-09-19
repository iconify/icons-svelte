<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odq-7dbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="odq-7dbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailleone" {...props}></Icon>
