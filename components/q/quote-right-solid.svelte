<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnz6y9byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnz6y9byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:quote-right-solid" {...props}></Icon>
