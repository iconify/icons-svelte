<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj46-921z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj46-921z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-horiz-square-line" {...props}></Icon>
