<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_xopgbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_xopgbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:pulse-solid" {...props}></Icon>
