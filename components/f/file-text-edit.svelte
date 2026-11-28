<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrc1pubwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrc1pubwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-text-edit" {...props}></Icon>
