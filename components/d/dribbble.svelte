<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr9x3pbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr9x3pbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dribbble" {...props}></Icon>
