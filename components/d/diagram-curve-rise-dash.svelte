<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi17iyctf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi17iyctf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:diagram-curve-rise-dash" {...props}></Icon>
