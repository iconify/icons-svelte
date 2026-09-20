<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dshqe4b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dshqe4b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parking-lights-fill" {...props}></Icon>
