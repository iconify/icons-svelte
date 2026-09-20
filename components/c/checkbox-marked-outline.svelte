<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejca9ogzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejca9ogzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-marked-outline" {...props}></Icon>
