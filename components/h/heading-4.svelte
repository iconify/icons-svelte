<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft8hti5fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft8hti5fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-4" {...props}></Icon>
