<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qugofnbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1792};
const content = `<path class="qugofnbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:i-cursor" {...props}></Icon>
