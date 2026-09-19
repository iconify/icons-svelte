<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upe21snco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upe21snco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:brain" {...props}></Icon>
