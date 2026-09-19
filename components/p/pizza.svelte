<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uouj_4bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":496};
const content = `<path class="uouj_4bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pizza" {...props}></Icon>
