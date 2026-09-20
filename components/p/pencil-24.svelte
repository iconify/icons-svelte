<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f65h7_qtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f65h7_qtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pencil-24" {...props}></Icon>
