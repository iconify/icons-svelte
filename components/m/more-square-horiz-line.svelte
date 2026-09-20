<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gui0q2a6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gui0q2a6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-square-horiz-line" {...props}></Icon>
