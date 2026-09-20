<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oixly2cla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oixly2cla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eclipse-che" {...props}></Icon>
