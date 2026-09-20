<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exz7v5bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="exz7v5bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:list-percentage" {...props}></Icon>
