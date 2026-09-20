<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocgok7zrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocgok7zrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:charging-battery-empty" {...props}></Icon>
