<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gner02b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gner02b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:remotemysql" {...props}></Icon>
