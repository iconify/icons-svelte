<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d5il6vccw.css';
import '../../css/r/r6psnwdnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d5il6vccw"/><path class="r6psnwdnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-alt-duotone" {...props}></Icon>
