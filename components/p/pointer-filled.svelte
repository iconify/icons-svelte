<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl_x3gf9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl_x3gf9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pointer-filled" {...props}></Icon>
