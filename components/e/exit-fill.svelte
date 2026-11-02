<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqfg2e1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjqfg2e1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exit-fill" {...props}></Icon>
