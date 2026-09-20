<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uapph2b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uapph2b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:messages-square" {...props}></Icon>
