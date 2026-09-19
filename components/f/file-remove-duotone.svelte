<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lhj0lixiu.css';
import '../../css/i/i63lgvbjp.css';
import '../../css/z/z7bc25blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lhj0lixiu"/><path class="i63lgvbjp"/><path class="z7bc25blt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-remove-duotone" {...props}></Icon>
