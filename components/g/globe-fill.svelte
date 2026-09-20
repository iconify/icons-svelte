<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_8mfx7kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_8mfx7kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:globe-fill" {...props}></Icon>
