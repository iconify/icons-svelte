<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmx89-dah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmx89-dah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:female" {...props}></Icon>
