<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn5_h39-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn5_h39-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:distrobox" {...props}></Icon>
