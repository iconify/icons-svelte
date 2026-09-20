<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbn4cobcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gbn4cobcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ghx" {...props}></Icon>
