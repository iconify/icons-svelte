<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_nwxbb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nwxbb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:element4" {...props}></Icon>
