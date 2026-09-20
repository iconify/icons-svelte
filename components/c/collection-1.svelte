<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwk220rgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwk220rgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:collection-1" {...props}></Icon>
