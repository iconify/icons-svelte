<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-2la_f4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-2la_f4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:play-square-fill" {...props}></Icon>
