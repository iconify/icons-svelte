<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvvdlbc1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvvdlbc1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:close" {...props}></Icon>
