<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksr8kl3ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksr8kl3ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:react-bootstrap" {...props}></Icon>
