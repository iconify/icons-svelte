<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxndvphjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":1024};
const content = `<path class="dxndvphjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:facebook" {...props}></Icon>
