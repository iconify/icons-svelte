<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbmr7ioil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbmr7ioil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-3x2" {...props}></Icon>
