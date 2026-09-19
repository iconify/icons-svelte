<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im9n4db7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="im9n4db7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:camera-circle-fill" {...props}></Icon>
