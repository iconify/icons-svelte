<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj3wil8tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wj3wil8tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:microphone" {...props}></Icon>
