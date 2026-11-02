<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fga-cy2vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fga-cy2vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-camera-off-fill" {...props}></Icon>
