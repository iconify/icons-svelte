<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/igwz4qbul.css';
import '../../css/e/e3b2urw8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="igwz4qbul"/><path class="e3b2urw8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:landing-duotone" {...props}></Icon>
