<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2qss64im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2qss64im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:heart-square-fill" {...props}></Icon>
