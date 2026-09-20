<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sprp5wehn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sprp5wehn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:google-drive-alt" {...props}></Icon>
