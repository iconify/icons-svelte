<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssho5bc1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ssho5bc1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bug" {...props}></Icon>
