<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t0vi6uguc.css';
import '../../css/l/l9jmerwwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t0vi6uguc"/><path class="l9jmerwwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-simple-duotone" {...props}></Icon>
