<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt7xtbczv.css';
import '../../css/f/fqgt3213z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt7xtbczv"/><path class="fqgt3213z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:5dive" {...props}></Icon>
