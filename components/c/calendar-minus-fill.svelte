<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_uink9fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_uink9fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-minus-fill" {...props}></Icon>
