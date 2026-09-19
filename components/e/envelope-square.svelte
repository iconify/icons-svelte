<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa9audbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="sa9audbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:envelope-square" {...props}></Icon>
