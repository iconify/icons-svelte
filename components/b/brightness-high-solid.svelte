<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iht2ggb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iht2ggb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:brightness-high-solid" {...props}></Icon>
