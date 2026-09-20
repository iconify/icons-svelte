<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhgco_s2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhgco_s2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:exclamation-triangle-solid" {...props}></Icon>
