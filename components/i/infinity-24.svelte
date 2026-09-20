<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_8bf5a3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_8bf5a3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:infinity-24" {...props}></Icon>
