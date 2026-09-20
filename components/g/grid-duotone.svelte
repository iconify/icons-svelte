<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zfbbd1bmk.css';
import '../../css/q/q8qr-0bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zfbbd1bmk"/><path class="q8qr-0bai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:grid-duotone" {...props}></Icon>
