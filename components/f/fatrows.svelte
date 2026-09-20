<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilic3tb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilic3tb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fatrows" {...props}></Icon>
