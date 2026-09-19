<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx-69zu8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nx-69zu8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:buttonb" {...props}></Icon>
