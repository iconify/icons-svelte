<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu7w1mhzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gu7w1mhzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:opencart" {...props}></Icon>
