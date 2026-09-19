<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx6fch0-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vx6fch0-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:loadingsix" {...props}></Icon>
