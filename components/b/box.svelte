<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd6f9ccio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd6f9ccio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box" {...props}></Icon>
