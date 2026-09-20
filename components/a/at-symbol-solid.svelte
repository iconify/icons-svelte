<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwy9wwbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwy9wwbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:at-symbol-solid" {...props}></Icon>
