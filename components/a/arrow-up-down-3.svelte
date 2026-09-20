<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m14mvl26y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m14mvl26y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-up-down-3" {...props}></Icon>
