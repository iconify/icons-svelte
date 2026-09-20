<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o23mbdcfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o23mbdcfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:genesis-l1" {...props}></Icon>
