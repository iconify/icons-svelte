<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b0n8abcgf.css';
import '../../css/e/e1uga3ojo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b0n8abcgf"/><path class="e1uga3ojo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-alarm-duotone" {...props}></Icon>
